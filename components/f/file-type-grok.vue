<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k1-xg5bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-grok" /></template>
<style>
.k1-xg5bfu {
  fill: var(--svg-color--d2d2d2, #d2d2d2);
  d: path("m12.819 19.326l9.295-6.9c.456-.339 1.107-.207 1.324.32c1.143 2.77.632 6.1-1.642 8.387s-5.437 2.788-8.329 1.646l-3.159 1.47c4.532 3.115 10.033 2.345 13.471-1.115c2.727-2.743 3.572-6.48 2.782-9.851l.007.007c-1.145-4.953.281-6.932 3.205-10.98l.207-.29l-3.846 3.868v-.012L12.816 19.329M10.9 21.004c-3.252-3.125-2.691-7.959.084-10.747c2.051-2.063 5.414-2.905 8.348-1.667l3.151-1.464a9 9 0 0 0-2.13-1.169A10.42 10.42 0 0 0 8.992 8.255c-2.952 2.97-3.88 7.532-2.286 11.427c1.19 2.91-.761 4.969-2.727 7.047c-.697.736-1.396 1.473-1.959 2.252l8.877-7.975");
}

</style>
