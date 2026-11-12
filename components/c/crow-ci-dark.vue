<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7yjv0aal.css';
import '../../css/x/xca1i3bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y7yjv0aal"/><path class="xca1i3bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:crow-ci-dark" /></template>
