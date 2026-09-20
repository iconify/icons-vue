<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_p73mbnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_p73mbnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:facebook-messenger-alt" /></template>
