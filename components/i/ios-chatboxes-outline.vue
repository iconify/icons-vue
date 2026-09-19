<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejq_vxbcb.css';
import '../../css/q/qcygcjg0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ejq_vxbcb"/><path class="qcygcjg0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-chatboxes-outline" /></template>
