<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x0rn5hb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0rn5hb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:comment-share" /></template>
