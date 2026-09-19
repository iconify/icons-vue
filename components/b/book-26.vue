<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kj73_vt_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="kj73_vt_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-26" /></template>
