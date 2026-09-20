<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3s2ijb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3s2ijb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-up-right" /></template>
