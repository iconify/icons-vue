<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuyf9rb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uuyf9rb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:hand-holding-dollar-light" /></template>
