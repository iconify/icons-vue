<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a17etlsmp.css';
import '../../css/g/g015acbcu.css';
import '../../css/m/mnelrmb_n.css';
import '../../css/w/wcp-8_b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a17etlsmp"/><path clip-rule="evenodd" class="g015acbcu"/><path clip-rule="evenodd" class="mnelrmb_n"/><path clip-rule="evenodd" class="wcp-8_b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-fork-bold-duotone" /></template>
