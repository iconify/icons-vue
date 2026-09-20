<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kaok-xlkj.css';
import '../../css/h/h5ggh0boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kaok-xlkj"/><path class="h5ggh0boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:key-skeleton" /></template>
