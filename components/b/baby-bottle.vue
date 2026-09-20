<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blusrlqbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blusrlqbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:baby-bottle" /></template>
