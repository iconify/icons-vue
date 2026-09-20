<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/no_cqmfti.css';
import '../../css/c/cmsj9noho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="no_cqmfti"/><path class="cmsj9noho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:cachyos-dark" /></template>
