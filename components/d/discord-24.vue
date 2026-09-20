<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a2xdvtgbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a2xdvtgbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:discord-24" /></template>
