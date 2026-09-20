<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6xh5bbvt.css';
import '../../css/d/df_pnlkgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d6xh5bbvt"/><path class="df_pnlkgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:compass-duotone-line" /></template>
