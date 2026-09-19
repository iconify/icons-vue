<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j8rd68b8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j8rd68b8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo-social:grooveshark" /></template>
