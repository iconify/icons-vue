<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-8kybbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b-8kybbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloudy-partly-night-filled" /></template>
