<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn3wpqudq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="dn3wpqudq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-vector-small-filled" /></template>
