<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/k/kscc-z.css';
import '../../css/m/m1gu2s.css';
import '../../css/n/neinwl.css';
import '../../css/s/so-from-60.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c kscc-z"/><path class="a0m25c m1gu2s"/><path class="a0m25c neinwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:alert" /></template>
