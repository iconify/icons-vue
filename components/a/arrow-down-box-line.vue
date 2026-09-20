<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npgdh3aap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npgdh3aap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-box-line" /></template>
