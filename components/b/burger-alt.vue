<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc4ch3rjw.css';
import '../../css/j/jczmvvbsl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wc4ch3rjw"/><path class="jczmvvbsl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:burger-alt" /></template>
