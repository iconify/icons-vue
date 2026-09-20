<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swzejqbqc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="swzejqbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:info-circle-filled" /></template>
