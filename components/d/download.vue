<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at3jokbwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at3jokbwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:download" /></template>
