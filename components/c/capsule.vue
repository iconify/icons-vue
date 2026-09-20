<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cwluzqb8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwluzqb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:capsule" /></template>
