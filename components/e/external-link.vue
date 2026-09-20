<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/e/et8gjv.css';
import '../../css/e/erpyod.css';
import '../../css/a/avyd9d.css';
import '../../css/s/so-from-42.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c et8gjv"/><path class="a0m25c erpyod"/><path class="a0m25c avyd9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:external-link" /></template>
