<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ct12hn0tg.css';
import '../../css/i/im4c1bc7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ct12hn0tg duoicon-secondary-layer"/><path class="duoicon-primary-layer im4c1bc7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:bookmark" /></template>
