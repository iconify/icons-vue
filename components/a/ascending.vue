<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8q1lbb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f8q1lbb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:ascending" /></template>
