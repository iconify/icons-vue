<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzpz-zbzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zzpz-zbzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:executable-16" /></template>
