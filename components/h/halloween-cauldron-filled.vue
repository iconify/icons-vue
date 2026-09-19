<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvaxjbbeb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wvaxjbbeb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-cauldron-filled" /></template>
