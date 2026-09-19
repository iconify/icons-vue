<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3wqb6ppo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v3wqb6ppo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:dna-double-helix" /></template>
