<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/o/om42epbiw.css';
import '../../css/k/kinx7jb3n.css';
import '../../css/a/a5ugidbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="om42epbiw"/><path class="kinx7jb3n"/><path class="a5ugidbaj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:document-previous" /></template>
