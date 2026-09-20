<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xfqbr3bdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfqbr3bdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-x-sharp" /></template>
