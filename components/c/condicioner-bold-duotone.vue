<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdx5upbas.css';
import '../../css/y/ykggxvo8b.css';
import '../../css/e/eb3ikh_mw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cdx5upbas"/><path class="ykggxvo8b"/><path clip-rule="evenodd" class="eb3ikh_mw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:condicioner-bold-duotone" /></template>
