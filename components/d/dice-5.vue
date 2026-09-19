<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fnqicwb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnqicwb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:dice-5" /></template>
