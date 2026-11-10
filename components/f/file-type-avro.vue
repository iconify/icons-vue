<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="r-89ldbqw"><path class="xsm7dqbrn"/><path class="zreyo3b7v"/><path class="ox7n1wxtk"/><path class="a_p7kd9cc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-avro" /></template>
<style>
.a_p7kd9cc {
  fill: var(--svg-color--1cccfc, #1cccfc);
  d: path("M30 27.858L15.779 12.105s-2.562-2.908-2.455-3.741s3.508 1.825 3.508 1.825s.378.364.737.302c.358-.06-.025-.657-.025-.657s-.588-1.365-.196-1.61c.395-.243 1.39.784 1.39.784s.25.258.51.189c.261-.071.121-.644.121-.644s-1.798-4.148-1.014-4.457c1.197-.474 2.901 2.958 3.473 4.027C21.972 8.418 30 27.859 30 27.859zM7.807 8.365s-.73.483.082 1.412c.746.856 1.41.411 1.41.411s.688-.42.028-1.214c-.874-1.049-1.52-.61-1.52-.61");
}

.ox7n1wxtk {
  fill: var(--svg-color--1cccfc, #1cccfc);
  d: path("M15.655 5.634s-.542.51.028 1.173c.423.492 1.055.19 1.055.19s.582-.327.14-1.016c-.575-.896-1.223-.347-1.223-.347m14.26 22.315l-21.55-9.6s-7.041-4.355-6.312-6.076c.71-1.665 6.986 1.69 7.65 1.845s1.034-.264 1.046-.557c.02-.423-.932-1.632-.438-2.148c.491-.515 2.1.488 2.1.488l1.305.903z");
}

.r-89ldbqw {
  stroke-width: var(--svg-stroke-width--0-797px, 0.797px);
}

.xsm7dqbrn {
  fill: var(--svg-color--0068e0, #0068e0);
  d: path("m9.427 18.639l1.228 3.752l19.223 5.482z");
}

.zreyo3b7v {
  fill: var(--svg-color--000094, #000094);
  d: path("M16.137 12.426c.236.936-.012 1.53-1.527 1.383l15.191 14.078c.173.07.203-.046.083-.222z");
}

</style>
