<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl6gc6mhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl6gc6mhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:announcement-alt-02-filled" /></template>
