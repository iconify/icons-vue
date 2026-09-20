<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa9u5v4ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa9u5v4ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-narrow-wide-fill" /></template>
