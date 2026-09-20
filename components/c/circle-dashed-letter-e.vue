<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty5syd2kn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty5syd2kn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-letter-e" /></template>
