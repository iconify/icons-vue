<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/p/p19e3a.css';
import '../../css/e/erpyod.css';
import '../../css/a/avyd9d.css';
import '../../css/s/so-from-36.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c p19e3a"/><path class="a0m25c erpyod"/><path class="a0m25c avyd9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:external-link-rounded" /></template>
