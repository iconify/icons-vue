<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="phi0nubpg"/><path class="rf-n2gbbn"/><path class="r3wtxubno"/><path class="jbxv1kbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-twig" /></template>
<style>
.jbxv1kbtz {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.3 21.323a1.753 1.753 0 1 1-.513-1.24a1.75 1.75 0 0 1 .513 1.24m4.675 0a1.753 1.753 0 1 1-.513-1.24a1.75 1.75 0 0 1 .513 1.24");
}

.phi0nubpg {
  fill: var(--svg-color--63bf6a, #63bf6a);
  d: path("M4.574 5.463c.262.4 2.5-1.608 4.454-1.161c2.061.472 4.014 3.724 4.848 13.7a40 40 0 0 1 3.541 3.61q.53.614 1.013 1.22a12 12 0 0 1 .229-1.4a12.3 12.3 0 0 1 1.981-4.4A19.15 19.15 0 0 0 17.272 7.9c-1.03-1.445-4.6-6.478-8.546-5.843c-2.544.408-4.426 2.997-4.152 3.406");
}

.r3wtxubno {
  fill: var(--svg-color--78dc50, #78dc50);
  d: path("M2.238 13.935c.145-.447 2.468-.259 4.54.293c2.5.666 7 2.344 11.651 8.606A12.54 12.54 0 0 1 20.279 30h-9.893a22 22 0 0 0-.175-4.62a14.9 14.9 0 0 0-2.459-7.158c-2.311-3.063-5.697-3.722-5.514-4.287");
}

.rf-n2gbbn {
  fill: var(--svg-color--74d74d, #74d74d);
  d: path("M24.4 30a69 69 0 0 1-.5-6.449c-.094-3.232.1-4.541.9-5.756c.193-.295 1.288-1.975 2.58-1.863c1.466.128 2.213 2.414 2.362 2.337c.175-.09-.36-3.543-2.532-4.431c-2.6-1.063-6.312 2.07-7.8 5.154a12.2 12.2 0 0 0-.857 2.81a32.6 32.6 0 0 0-.71 8.2Z");
}

</style>
