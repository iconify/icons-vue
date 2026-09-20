<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa5efpwgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa5efpwgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:bitly" /></template>
