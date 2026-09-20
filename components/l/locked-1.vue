<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tetbrrbka.css';
import '../../css/j/j9auzlb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tetbrrbka"/><path class="j9auzlb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:locked-1" /></template>
