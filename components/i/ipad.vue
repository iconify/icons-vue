<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/b/b7c5wh5qe.css';
import '../../css/o/o5hmfpl1w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGeATNtgLq"><g class="s9cl3zbei"><rect class="b7c5wh5qe"/><path class="o5hmfpl1w"/></g></mask></defs><path mask="url(#SVGeATNtgLq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:ipad" /></template>
