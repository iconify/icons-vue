<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnolt0wrb.css';
import '../../css/q/q6oeacb7k.css';
import '../../css/l/lflficb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnolt0wrb"/><path class="q6oeacb7k"/><path class="lflficb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-duotone" /></template>
