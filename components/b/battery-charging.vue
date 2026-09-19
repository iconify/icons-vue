<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njzkcqbpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njzkcqbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:battery-charging" /></template>
