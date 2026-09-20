<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/k/kgsk8t.css';
import '../../css/s/sqpi1o.css';
import '../../css/n/neinwl.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c kgsk8t"/><path class="a0m25c sqpi1o"/><path class="a0m25c neinwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:alert-square" /></template>
