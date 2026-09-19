<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/weomk1dpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="weomk1dpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:cpan" /></template>
