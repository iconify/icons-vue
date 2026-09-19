<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzsd_-k8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzsd_-k8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dbase" /></template>
