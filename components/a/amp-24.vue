<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljfzoqbhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ljfzoqbhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:amp-24" /></template>
