<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks6ph22qk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks6ph22qk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrow-right-square-filled" /></template>
