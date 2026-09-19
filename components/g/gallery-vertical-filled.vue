<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmch1189h.css';
import '../../css/n/n_0uj0b-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="zmch1189h"/><path class="n_0uj0b-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:gallery-vertical-filled" /></template>
