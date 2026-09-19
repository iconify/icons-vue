<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3kl9nb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3kl9nb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-sad" /></template>
