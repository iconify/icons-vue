<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lczf7rbjq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lczf7rbjq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:keybase" /></template>
