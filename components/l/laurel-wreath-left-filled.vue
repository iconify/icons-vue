<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggsab6nmw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggsab6nmw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:laurel-wreath-left-filled" /></template>
