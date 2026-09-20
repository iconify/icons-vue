<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3dte_aui.css';
import '../../css/p/p51mxvbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3dte_aui"/><path class="p51mxvbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ctr" /></template>
