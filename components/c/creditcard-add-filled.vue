<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt8wifbth.css';
import '../../css/k/kdpqefbdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt8wifbth"/><path class="kdpqefbdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:creditcard-add-filled" /></template>
