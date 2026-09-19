<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f6q5qubpi.css';
import '../../css/x/xy6iblzmn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUIY3jcJY"><g class="aql7dnt-u"><path class="f6q5qubpi"/><path class="xy6iblzmn"/></g></mask></defs><path mask="url(#SVGUIY3jcJY)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:file-addition" /></template>
