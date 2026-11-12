<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt9f2zz1g"/><path class="ry4h5fb7w"/><path class="iq4y8qctn"/><path class="kquyjabxs"/><path class="pczff7gss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:leaf-bold-duotone" /></template>
<style>
.iq4y8qctn {
  fill: currentColor;
  d: path("M18.6143 7.88574C19.1839 9.10061 19.5906 10.399 19.8105 11.6895C19.935 12.4197 20 13.1474 20 13.8564C20 18.3539 16.4183 22 12 22V14.5L18.6143 7.88574Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.kquyjabxs {
  fill: currentColor;
  d: path("M19.8105 11.6895C19.935 12.4197 20 13.1474 20 13.8564C20 18.3539 16.4183 22 12 22V19.5L19.8105 11.6895Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.nt9f2zz1g {
  fill: currentColor;
  d: path("M12 2C12.4992 2 12.9986 2.10821 13.4629 2.3252C14.5712 2.84325 15.5689 3.62056 16.4316 4.56836C17.3062 5.52916 18.0422 6.66557 18.6143 7.88574C19.1839 9.10061 19.5906 10.399 19.8105 11.6895C19.935 12.4197 20 13.1474 20 13.8564C20 18.3539 16.4183 22 12 22V2Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pczff7gss {
  fill: currentColor;
  d: path("M12 22C7.58172 22 4 18.3539 4 13.8564C4.0001 9.39433 6.55344 4.18719 10.5371 2.3252C11.0014 2.10821 11.5008 2 12 2V22Z");
}

.ry4h5fb7w {
  fill: currentColor;
  d: path("M16.4316 4.56836C17.3062 5.52916 18.0422 6.66557 18.6143 7.88574C19.1839 9.10061 19.5906 10.399 19.8105 11.6895C19.935 12.4197 20 13.1474 20 13.8564C20 18.3539 16.4183 22 12 22V9L16.4316 4.56836Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
