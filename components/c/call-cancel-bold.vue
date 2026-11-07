<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_hf_9u3p.css';
import '../../css/b/b778k0btr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_hf_9u3p"/><path class="b778k0btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-cancel-bold" /></template>
