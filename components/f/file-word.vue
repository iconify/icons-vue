<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myiznqbfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="myiznqbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:file-word" /></template>
