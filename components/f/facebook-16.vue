<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myqkzzb1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="myqkzzb1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:facebook-16" /></template>
