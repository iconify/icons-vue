<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4jcqrw0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="s4jcqrw0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chevron-up-square-fill" /></template>
