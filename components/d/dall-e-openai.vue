<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n1lsf0bnc.css';
import '../../css/j/jwgxi-b0m.css';
import '../../css/o/oetgeybih.css';
import '../../css/e/e7fn94kyy.css';
import '../../css/p/pw07jnici.css';
import '../../css/w/w0o3ber3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="jwgxi-b0m"/><path class="oetgeybih"/><path class="e7fn94kyy"/><path class="pw07jnici"/><path class="w0o3ber3e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:dall-e-openai" /></template>
