<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/h/h9qj9o6mz.css';
import '../../css/u/u3lq9483n.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzYuCQy4K"><g class="v3_i3wktz"><rect class="h9qj9o6mz"/><path class="u3lq9483n"/></g></mask></defs><path mask="url(#SVGzYuCQy4K)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-text-right-one" /></template>
