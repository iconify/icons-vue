<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn48pqbnt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sn48pqbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-u-turn-up-line-solid" /></template>
