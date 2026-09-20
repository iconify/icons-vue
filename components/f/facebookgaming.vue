<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo8qe8byy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo8qe8byy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:facebookgaming" /></template>
