<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5qnn3pkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s5qnn3pkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:flag-up" /></template>
