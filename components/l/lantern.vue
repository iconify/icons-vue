<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/opfvhq6uh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opfvhq6uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:lantern" /></template>
