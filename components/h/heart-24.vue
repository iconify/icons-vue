<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9ufr8bnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y9ufr8bnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:heart-24" /></template>
