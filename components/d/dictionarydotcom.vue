<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3z04ac9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3z04ac9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dictionarydotcom" /></template>
