<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyax_mekw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyax_mekw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:linuxprofessionalinstitute" /></template>
