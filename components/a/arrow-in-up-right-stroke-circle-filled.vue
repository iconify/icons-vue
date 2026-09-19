<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dncihhclw.css';
import '../../css/a/a2k6oubdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dncihhclw"/><path class="a2k6oubdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-right-stroke-circle-filled" /></template>
