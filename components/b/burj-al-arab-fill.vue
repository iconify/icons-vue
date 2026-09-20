<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iauax3bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iauax3bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:burj-al-arab-fill" /></template>
