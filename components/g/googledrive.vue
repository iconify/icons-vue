<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egf1rkb1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egf1rkb1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:googledrive" /></template>
