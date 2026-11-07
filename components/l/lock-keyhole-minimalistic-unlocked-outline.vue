<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5nlnvurm.css';
import '../../css/u/u70j8007s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y5nlnvurm"/><path clip-rule="evenodd" class="u70j8007s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-keyhole-minimalistic-unlocked-outline" /></template>
