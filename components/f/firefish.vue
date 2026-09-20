<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3uqrrb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3uqrrb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:firefish" /></template>
