<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1t1l7b2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1t1l7b2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:cyberdefenders" /></template>
