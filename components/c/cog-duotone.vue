<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pst0mi77l.css';
import '../../css/b/bhja3k33r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pst0mi77l"/><path class="bhja3k33r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cog-duotone" /></template>
