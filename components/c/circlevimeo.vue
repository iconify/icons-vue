<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hk9jk_8nt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="hk9jk_8nt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:circlevimeo" /></template>
