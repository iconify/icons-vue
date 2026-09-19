<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn1v9ob2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn1v9ob2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:folder-open" /></template>
