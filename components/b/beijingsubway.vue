<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jmg9u37la.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmg9u37la"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:beijingsubway" /></template>
