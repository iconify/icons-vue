<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cducd7zor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cducd7zor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:loader-4" /></template>
