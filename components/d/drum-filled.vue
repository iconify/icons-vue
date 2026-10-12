<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7o7vzk5e.css';
import '../../css/j/j-89n_bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7o7vzk5e"/><path class="j-89n_bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:drum-filled" /></template>
