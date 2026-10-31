<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvs3sen_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvs3sen_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bath-round" /></template>
