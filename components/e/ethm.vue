<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj9_93b9n.css';
import '../../css/j/j-ja1cc5v.css';
import '../../css/q/qkn211b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tj9_93b9n"/><path class="j-ja1cc5v"/><path class="qkn211b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:ethm" /></template>
