<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jfemr9pud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jfemr9pud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ease-out" /></template>
