<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/arhog_kvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="arhog_kvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:courthouse" /></template>
