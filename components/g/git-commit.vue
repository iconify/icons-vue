<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcuquob1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcuquob1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:git-commit" /></template>
