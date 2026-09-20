<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fr6ohd4vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fr6ohd4vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:keras" /></template>
