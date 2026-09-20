<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd2-gvknj.css';
import '../../css/n/niw2nrbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vd2-gvknj"/><path class="niw2nrbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:facebook" /></template>
