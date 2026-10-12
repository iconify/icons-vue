<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whfucbber.css';
import '../../css/v/v1vmo492j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="whfucbber"/><path class="v1vmo492j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:chevron-double-up-20" /></template>
