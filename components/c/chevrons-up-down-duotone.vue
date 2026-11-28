<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqpgrsbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqpgrsbwp primary"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:chevrons-up-down-duotone" /></template>
