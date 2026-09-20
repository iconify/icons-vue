<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stica__rp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="stica__rp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lsicon:edit-filled" /></template>
