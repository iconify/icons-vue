<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/or0-msbfm.css';
import '../../css/q/qtdly1ban.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="or0-msbfm"/><path class="qtdly1ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:at-sign" /></template>
