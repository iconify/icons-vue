<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uh0m0cy5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uh0m0cy5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:acrobatic" /></template>
