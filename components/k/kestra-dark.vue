<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgtmarbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wgtmarbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kestra-dark" /></template>
