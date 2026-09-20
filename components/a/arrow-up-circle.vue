<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/p/p0bift.css';
import '../../css/e/eygq0a.css';
import '../../css/r/rp-3po.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c p0bift"/><path class="a0m25c eygq0a"/><path class="a0m25c rp-3po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrow-up-circle" /></template>
