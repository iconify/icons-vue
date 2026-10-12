<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lj96y1j8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lj96y1j8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:folders-fill-20" /></template>
