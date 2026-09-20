<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loygki_gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loygki_gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cog" /></template>
