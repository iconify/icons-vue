<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f6q5qubpi.css';
import '../../css/y/ywt5xtc6b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfsP0WyOh"><g class="aql7dnt-u"><path class="f6q5qubpi"/><path class="ywt5xtc6b"/></g></mask></defs><path mask="url(#SVGfsP0WyOh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-success" /></template>
