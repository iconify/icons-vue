<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irx4tpg6l.css';
import '../../css/x/x7l00djaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="irx4tpg6l"/><path class="x7l00djaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:edit-solid" /></template>
