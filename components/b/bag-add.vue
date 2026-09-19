<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzp4omb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zzp4omb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-add" /></template>
