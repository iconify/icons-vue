<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue7ba3bjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="ue7ba3bjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:home-option" /></template>
