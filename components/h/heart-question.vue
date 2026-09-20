<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ajres5ior.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ajres5ior"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:heart-question" /></template>
