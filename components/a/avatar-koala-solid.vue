<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nl78ogquz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nl78ogquz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-koala-solid" /></template>
