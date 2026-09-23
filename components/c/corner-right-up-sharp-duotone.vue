<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrngubb6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rrngubb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-right-up-sharp-duotone" /></template>
